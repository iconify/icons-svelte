<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdtwd7bjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kdtwd7bjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:numeric-8-box-outline" {...props}></Icon>
