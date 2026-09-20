<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_kea9vfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f_kea9vfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-swimming-in-waters" {...props}></Icon>
