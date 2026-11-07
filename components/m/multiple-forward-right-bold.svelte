<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkvbobd_g.css';
import '../../css/p/pfr06xbye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vkvbobd_g"/><path clip-rule="evenodd" class="pfr06xbye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:multiple-forward-right-bold" {...props}></Icon>
