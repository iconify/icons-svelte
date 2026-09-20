<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3kho1bus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3kho1bus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:discord" {...props}></Icon>
