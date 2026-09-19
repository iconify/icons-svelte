<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz1q1stlw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fz1q1stlw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cloud-rain-filled" {...props}></Icon>
