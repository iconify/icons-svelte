<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/giliqpzpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="giliqpzpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:libra-fill" {...props}></Icon>
