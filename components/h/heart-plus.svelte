<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpw8u2-_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hpw8u2-_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:heart-plus" {...props}></Icon>
