<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7_ca8bkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i7_ca8bkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:head-side-mask" {...props}></Icon>
