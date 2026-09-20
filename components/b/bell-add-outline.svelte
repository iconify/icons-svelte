<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgzs6hb4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jgzs6hb4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bell-add-outline" {...props}></Icon>
