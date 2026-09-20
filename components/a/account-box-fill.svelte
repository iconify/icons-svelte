<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cts12dmrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cts12dmrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:account-box-fill" {...props}></Icon>
