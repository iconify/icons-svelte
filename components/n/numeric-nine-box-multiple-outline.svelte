<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k19mh358r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k19mh358r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:numeric-nine-box-multiple-outline" {...props}></Icon>
