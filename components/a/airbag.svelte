<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujr83xbzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ujr83xbzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:airbag" {...props}></Icon>
