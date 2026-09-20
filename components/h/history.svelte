<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnxhovbed.css';
import '../../css/o/o5bl2wrlr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pnxhovbed"/><path class="o5bl2wrlr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:history" {...props}></Icon>
