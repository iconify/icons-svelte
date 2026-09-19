<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0kol9bky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l0kol9bky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:arrow-up-left" {...props}></Icon>
