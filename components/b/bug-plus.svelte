<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pl47__mjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pl47__mjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:bug-plus" {...props}></Icon>
