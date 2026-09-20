<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uonq2q-9z.css';
import '../../css/w/w-n1usl-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uonq2q-9z"/><path class="w-n1usl-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:deno" {...props}></Icon>
