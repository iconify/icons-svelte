<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sm71xnlzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sm71xnlzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:pen-square-solid" {...props}></Icon>
