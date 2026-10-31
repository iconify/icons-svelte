<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-at6i8pn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-at6i8pn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:paste-fill-round" {...props}></Icon>
