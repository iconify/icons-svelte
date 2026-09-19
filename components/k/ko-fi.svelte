<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fq22e_95b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fq22e_95b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:ko-fi" {...props}></Icon>
