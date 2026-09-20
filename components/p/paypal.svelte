<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tn0c3r6yz.css';
import '../../css/z/zbdow5bzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tn0c3r6yz"/><path class="zbdow5bzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:paypal" {...props}></Icon>
