<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuo1t367k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cuo1t367k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bars-3-center-left-solid" {...props}></Icon>
