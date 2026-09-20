<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hja23dbah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="hja23dbah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:louder" {...props}></Icon>
