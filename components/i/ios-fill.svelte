<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubgk3rb-x.css';
import '../../css/k/kx15g1jff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ubgk3rb-x"/><path clip-rule="evenodd" class="kx15g1jff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ios-fill" {...props}></Icon>
