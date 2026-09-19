<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pali_db3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="pali_db3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:chevron-unfold-10" {...props}></Icon>
