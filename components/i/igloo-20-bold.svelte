<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4fxe_2wu.css';
import '../../css/q/qb-anoa-e.css';
import '../../css/f/fxwh4ibmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g4fxe_2wu"/><path class="qb-anoa-e"/><path class="fxwh4ibmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:igloo-20-bold" {...props}></Icon>
