<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajpqcixii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ajpqcixii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cash-chargeback" {...props}></Icon>
