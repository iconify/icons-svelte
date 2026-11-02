<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oubgc4blb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oubgc4blb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:process-fill" {...props}></Icon>
