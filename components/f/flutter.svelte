<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_paajbki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_paajbki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:flutter" {...props}></Icon>
