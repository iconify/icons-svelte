<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgjiwf5-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="fgjiwf5-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:asset-outdoor" {...props}></Icon>
