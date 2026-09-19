<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aadbtqr2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aadbtqr2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:align-left" {...props}></Icon>
