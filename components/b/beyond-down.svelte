<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrl35cbgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jrl35cbgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:beyond-down" {...props}></Icon>
