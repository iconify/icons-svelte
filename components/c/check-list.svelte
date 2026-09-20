<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p770-7bjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p770-7bjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:check-list" {...props}></Icon>
