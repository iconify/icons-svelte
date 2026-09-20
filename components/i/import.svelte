<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8qkxmpel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m8qkxmpel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:import" {...props}></Icon>
