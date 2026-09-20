<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_xn3hb7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t_xn3hb7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:message-circle-minus" {...props}></Icon>
