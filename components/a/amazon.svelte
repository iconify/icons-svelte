<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/audx4-b0p.css';
import '../../css/p/pwd6rdbok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="audx4-b0p"/><path class="pwd6rdbok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:amazon" {...props}></Icon>
