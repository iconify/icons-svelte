<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyu2l48ig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eyu2l48ig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:paypal-logo-block" {...props}></Icon>
