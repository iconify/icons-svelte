<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okq2mbbpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="okq2mbbpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:flour" {...props}></Icon>
