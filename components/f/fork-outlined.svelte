<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnq6aobdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gnq6aobdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:fork-outlined" {...props}></Icon>
