<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr-3k3jjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pr-3k3jjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:mail-x" {...props}></Icon>
