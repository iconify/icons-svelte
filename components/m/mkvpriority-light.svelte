<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8ebo54iz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z8ebo54iz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mkvpriority-light" {...props}></Icon>
