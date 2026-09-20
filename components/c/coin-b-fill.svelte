<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqr4zbbdb.css';
import '../../css/k/kmp8rebtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqr4zbbdb"/><path class="kmp8rebtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:coin-b-fill" {...props}></Icon>
