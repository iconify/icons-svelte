<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9k1dtb8p.css';
import '../../css/s/sn4crhb1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f9k1dtb8p"/><path clip-rule="evenodd" class="sn4crhb1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:magic-hat-line" {...props}></Icon>
