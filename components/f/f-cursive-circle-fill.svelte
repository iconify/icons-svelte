<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0j1o-b1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="k0j1o-b1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:f-cursive-circle-fill" {...props}></Icon>
