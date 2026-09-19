<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4nrrlban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y4nrrlban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:arrow-up-right" {...props}></Icon>
