<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmqu1qs-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zmqu1qs-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:lorry-delivery" {...props}></Icon>
