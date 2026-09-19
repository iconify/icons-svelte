<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8iec2qwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":27,"height":24};
const content = `<path class="v8iec2qwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:day-haze" {...props}></Icon>
