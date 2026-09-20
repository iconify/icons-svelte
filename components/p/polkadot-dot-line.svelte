<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvdwicxgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cvdwicxgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:polkadot-dot-line" {...props}></Icon>
