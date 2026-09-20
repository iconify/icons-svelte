<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_yv9lbiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x_yv9lbiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:arrow-right-square-line" {...props}></Icon>
