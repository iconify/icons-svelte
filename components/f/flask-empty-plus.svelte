<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf7be2b3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tf7be2b3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flask-empty-plus" {...props}></Icon>
