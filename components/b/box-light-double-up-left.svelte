<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzdioebup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="lzdioebup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-double-up-left" {...props}></Icon>
