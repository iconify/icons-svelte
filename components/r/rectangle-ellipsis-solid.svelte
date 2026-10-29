<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qu2bbhn-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qu2bbhn-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:rectangle-ellipsis-solid" {...props}></Icon>
