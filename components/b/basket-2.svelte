<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0-7ckzpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u0-7ckzpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:basket-2" {...props}></Icon>
