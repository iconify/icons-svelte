<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw604pc6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qw604pc6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:heart-break" {...props}></Icon>
