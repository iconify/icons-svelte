<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pymbvdbsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pymbvdbsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:panel-right-contract" {...props}></Icon>
