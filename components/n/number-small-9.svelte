<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p54ufnf5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p54ufnf5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:number-small-9" {...props}></Icon>
