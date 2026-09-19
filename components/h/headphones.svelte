<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhx6xt5an.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qhx6xt5an"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:headphones" {...props}></Icon>
