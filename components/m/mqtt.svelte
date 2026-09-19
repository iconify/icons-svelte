<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8nol0b7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c8nol0b7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:mqtt" {...props}></Icon>
