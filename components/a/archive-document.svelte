<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkoy5f77i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="nkoy5f77i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:archive-document" {...props}></Icon>
