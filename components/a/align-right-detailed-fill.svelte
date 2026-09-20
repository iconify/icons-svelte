<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1ryztnrd.css';
import '../../css/n/n6zdheb6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1ryztnrd"/><path clip-rule="evenodd" class="n6zdheb6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:align-right-detailed-fill" {...props}></Icon>
