<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft85d9bxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ft85d9bxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:objects-vertical-center" {...props}></Icon>
