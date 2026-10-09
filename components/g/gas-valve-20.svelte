<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wccquhbix.css';
import '../../css/f/fkjo-obco.css';
import '../../css/s/shl882bup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wccquhbix"/><path class="fkjo-obco"/><path class="shl882bup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gas-valve-20" {...props}></Icon>
