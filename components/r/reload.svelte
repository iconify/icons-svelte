<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufrhj6b5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ufrhj6b5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:reload" {...props}></Icon>
