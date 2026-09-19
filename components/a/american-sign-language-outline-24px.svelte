<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0iqixjtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0iqixjtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:american-sign-language-outline-24px" {...props}></Icon>
