<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0z6mwsbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0z6mwsbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:angular" {...props}></Icon>
