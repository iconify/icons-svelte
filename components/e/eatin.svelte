<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzd27gicd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="kzd27gicd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:eatin" {...props}></Icon>
