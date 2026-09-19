<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqkpo4bpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nqkpo4bpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:dots-three-vertical" {...props}></Icon>
