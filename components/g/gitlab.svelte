<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2cn_abmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="f2cn_abmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:gitlab" {...props}></Icon>
