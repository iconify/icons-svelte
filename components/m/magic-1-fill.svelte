<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gaiydvbku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gaiydvbku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:magic-1-fill" {...props}></Icon>
