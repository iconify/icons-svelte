<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2oymvbqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2oymvbqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:git-compare-fill" {...props}></Icon>
