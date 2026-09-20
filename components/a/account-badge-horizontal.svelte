<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj5gpvznm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fj5gpvznm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-badge-horizontal" {...props}></Icon>
