<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7gxsk0ha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u7gxsk0ha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:frigate" {...props}></Icon>
