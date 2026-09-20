<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/podgzbc_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="podgzbc_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:chalk" {...props}></Icon>
