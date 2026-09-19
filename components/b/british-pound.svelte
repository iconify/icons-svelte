<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otoqyqb2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="otoqyqb2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:british-pound" {...props}></Icon>
