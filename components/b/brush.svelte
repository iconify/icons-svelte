<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezvfgro8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ezvfgro8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:brush" {...props}></Icon>
