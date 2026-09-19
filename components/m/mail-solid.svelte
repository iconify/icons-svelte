<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uf7a0hbiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="uf7a0hbiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:mail-solid" {...props}></Icon>
