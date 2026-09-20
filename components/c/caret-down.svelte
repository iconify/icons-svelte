<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue87y9bea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ue87y9bea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:caret-down" {...props}></Icon>
