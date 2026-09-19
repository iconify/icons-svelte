<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ciupeob0b.css';
import '../../css/e/evzchhb-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ciupeob0b"/><path class="evzchhb-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:automobile" {...props}></Icon>
