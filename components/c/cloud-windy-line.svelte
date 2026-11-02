<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_zhecb8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_zhecb8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cloud-windy-line" {...props}></Icon>
