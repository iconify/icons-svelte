<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7260r08q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="b7260r08q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:pinterest" {...props}></Icon>
