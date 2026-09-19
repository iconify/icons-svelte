<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wzy-jac3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wzy-jac3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:play-circle-20-solid" {...props}></Icon>
