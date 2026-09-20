<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvmp6ybyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvmp6ybyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:puzzle-star-outline" {...props}></Icon>
