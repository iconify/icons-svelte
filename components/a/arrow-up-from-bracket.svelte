<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkmwn-55o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="pkmwn-55o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:arrow-up-from-bracket" {...props}></Icon>
