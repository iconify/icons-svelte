<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbpqthb8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b hbpqthb8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:deepseek" {...props}></Icon>
