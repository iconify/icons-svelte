<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzjz2-bvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="bzjz2-bvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:letter" {...props}></Icon>
