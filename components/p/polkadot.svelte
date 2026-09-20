<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e35kyaccs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e35kyaccs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:polkadot" {...props}></Icon>
