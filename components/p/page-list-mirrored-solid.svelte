<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlpkc4bvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="qlpkc4bvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:page-list-mirrored-solid" {...props}></Icon>
