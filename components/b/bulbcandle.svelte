<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcpzw0bzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kcpzw0bzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bulbcandle" {...props}></Icon>
