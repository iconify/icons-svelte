<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqc4vabyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uqc4vabyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:phone-hangup-line" {...props}></Icon>
