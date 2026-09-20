<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd-qr9bww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nd-qr9bww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:basic-attention-token" {...props}></Icon>
