<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/quobgb7ei.css';
import '../../css/s/s3cqxlbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="quobgb7ei"/><circle class="s3cqxlbus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:file-image-stroke-12" {...props}></Icon>
