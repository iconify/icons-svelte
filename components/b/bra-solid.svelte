<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kj481lbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kj481lbfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bra-solid" {...props}></Icon>
