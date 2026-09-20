<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_3zf4ikc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x_3zf4ikc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alert-plus" {...props}></Icon>
