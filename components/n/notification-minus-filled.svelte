<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6w1e-blf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u6w1e-blf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:notification-minus-filled" {...props}></Icon>
