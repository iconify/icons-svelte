<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f53sku4ar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f53sku4ar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:dresser-solid" {...props}></Icon>
