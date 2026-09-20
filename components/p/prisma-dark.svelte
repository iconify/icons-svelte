<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f16bk7bqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":310};
const content = `<path class="f16bk7bqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:prisma-dark" {...props}></Icon>
