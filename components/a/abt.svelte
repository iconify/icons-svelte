<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkhgmop_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mkhgmop_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:abt" {...props}></Icon>
