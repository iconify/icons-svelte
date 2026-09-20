<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/os05-0bel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="os05-0bel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:file-excel" {...props}></Icon>
