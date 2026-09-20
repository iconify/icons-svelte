<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok1z80fpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ok1z80fpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-wearing-cowboy-hat-holding-coiled-rope" {...props}></Icon>
