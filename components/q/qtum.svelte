<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4r1u1cta.css';
import '../../css/k/kmh9fqkcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t4r1u1cta"/><path class="kmh9fqkcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:qtum" {...props}></Icon>
