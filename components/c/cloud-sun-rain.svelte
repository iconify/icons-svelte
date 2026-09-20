<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dco9n2bsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dco9n2bsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:cloud-sun-rain" {...props}></Icon>
