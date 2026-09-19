<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysga9xgmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ysga9xgmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:file-earmark-code-fill" {...props}></Icon>
