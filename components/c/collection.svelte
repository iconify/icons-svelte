<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pus5ae97y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pus5ae97y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:collection" {...props}></Icon>
