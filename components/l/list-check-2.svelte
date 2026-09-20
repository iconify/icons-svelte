<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ui60a30tv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ui60a30tv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:list-check-2" {...props}></Icon>
