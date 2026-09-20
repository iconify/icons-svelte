<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6c7gbb4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n6c7gbb4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:nano-staged" {...props}></Icon>
