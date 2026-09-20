<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajodv2bql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ajodv2bql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:jigsaw-filled" {...props}></Icon>
