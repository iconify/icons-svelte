<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4h3a_bxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c4h3a_bxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:jack-16" {...props}></Icon>
