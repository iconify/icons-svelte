<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jv7o6gbgs.css';
import '../../css/a/a9nhzacts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jv7o6gbgs"/><path class="a9nhzacts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bell-minus" {...props}></Icon>
