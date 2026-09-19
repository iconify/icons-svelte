<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gl3pk4bqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gl3pk4bqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:amd" {...props}></Icon>
