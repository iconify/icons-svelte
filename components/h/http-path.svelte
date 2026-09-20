<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szit17v3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="szit17v3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:http-path" {...props}></Icon>
