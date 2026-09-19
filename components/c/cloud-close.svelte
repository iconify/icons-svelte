<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrtg64pfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wrtg64pfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:cloud-close" {...props}></Icon>
