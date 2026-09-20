<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofpqxnb0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ofpqxnb0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:dice2" {...props}></Icon>
