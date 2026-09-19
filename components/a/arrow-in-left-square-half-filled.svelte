<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ooaqbg7av.css';
import '../../css/l/l3bwhaczb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ooaqbg7av"/><path class="l3bwhaczb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-in-left-square-half-filled" {...props}></Icon>
