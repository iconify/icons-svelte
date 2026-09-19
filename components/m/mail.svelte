<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj6h2wbzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":614};
const content = `<path class="gj6h2wbzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:mail" {...props}></Icon>
