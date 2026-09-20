<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgnr7vmgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tgnr7vmgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:plus" {...props}></Icon>
