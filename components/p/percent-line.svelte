<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_pkvebfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_pkvebfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:percent-line" {...props}></Icon>
