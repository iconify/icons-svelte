<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktonl8bjx.css';
import '../../css/h/h8ocnybfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ktonl8bjx"/><path class="h8ocnybfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:after-effects" {...props}></Icon>
