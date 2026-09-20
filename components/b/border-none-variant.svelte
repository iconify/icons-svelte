<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrtmj5yhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jrtmj5yhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:border-none-variant" {...props}></Icon>
