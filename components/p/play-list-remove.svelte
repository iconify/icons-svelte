<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jog5b1b3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jog5b1b3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:play-list-remove" {...props}></Icon>
