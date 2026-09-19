<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q83s8q5he.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q83s8q5he"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bars-3-bottom-left-solid" {...props}></Icon>
