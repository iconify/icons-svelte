<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3n-s8zjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g3n-s8zjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-wallet-alt" {...props}></Icon>
