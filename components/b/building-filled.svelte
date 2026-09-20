<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ci8y9zdxq.css';
import '../../css/p/p2cix6gor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ci8y9zdxq"/><path class="p2cix6gor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:building-filled" {...props}></Icon>
