<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds_jc8x7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ds_jc8x7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:asian-noodles" {...props}></Icon>
