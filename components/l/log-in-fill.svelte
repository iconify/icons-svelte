<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3ky9_rfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v3ky9_rfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:log-in-fill" {...props}></Icon>
