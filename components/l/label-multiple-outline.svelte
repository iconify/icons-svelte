<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-fyg8bfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-fyg8bfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:label-multiple-outline" {...props}></Icon>
