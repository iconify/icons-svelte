<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evo6y-hhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="evo6y-hhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:bars" {...props}></Icon>
