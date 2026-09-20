<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfe_h5bhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vfe_h5bhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:expand-left-right-line" {...props}></Icon>
