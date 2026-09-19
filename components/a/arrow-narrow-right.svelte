<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/so7h_yp_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="so7h_yp_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:arrow-narrow-right" {...props}></Icon>
