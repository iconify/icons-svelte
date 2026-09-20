<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_zl1tdsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="j_zl1tdsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:empty-battery" {...props}></Icon>
