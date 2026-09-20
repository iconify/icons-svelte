<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqbdyobxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kqbdyobxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:asterisk-2-fill" {...props}></Icon>
