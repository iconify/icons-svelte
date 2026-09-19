<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hax_fhbww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hax_fhbww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cloud-rain-wind" {...props}></Icon>
