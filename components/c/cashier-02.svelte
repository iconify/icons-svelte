<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxcfvxjhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxcfvxjhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cashier-02" {...props}></Icon>
