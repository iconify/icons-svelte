<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvzoaacaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gvzoaacaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:git-merge-fill" {...props}></Icon>
