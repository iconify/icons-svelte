<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p37mgybgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="p37mgybgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:folder-arrow-up-fill" {...props}></Icon>
