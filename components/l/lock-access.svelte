<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qu71x2f-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qu71x2f-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:lock-access" {...props}></Icon>
