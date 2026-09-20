<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyxzz3b3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uyxzz3b3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:flowith" {...props}></Icon>
