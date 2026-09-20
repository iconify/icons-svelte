<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icgs5jzlf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="icgs5jzlf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:expand-up-down-fill" {...props}></Icon>
