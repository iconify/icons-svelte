<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdanhhkbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdanhhkbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:acorn" {...props}></Icon>
