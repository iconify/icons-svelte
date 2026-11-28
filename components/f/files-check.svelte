<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxyp99b3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxyp99b3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:files-check" {...props}></Icon>
