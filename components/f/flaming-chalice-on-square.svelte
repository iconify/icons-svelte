<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g81wb51pv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="g81wb51pv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:flaming-chalice-on-square" {...props}></Icon>
