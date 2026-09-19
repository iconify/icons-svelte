<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmvn587za.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jmvn587za"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bars-3-bottom-right-solid" {...props}></Icon>
