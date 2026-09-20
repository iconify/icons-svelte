<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uc05y9bou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uc05y9bou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:paypal" {...props}></Icon>
