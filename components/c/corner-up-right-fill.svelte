<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsnmn6bud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jsnmn6bud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:corner-up-right-fill" {...props}></Icon>
