<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t05ljv1oa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t05ljv1oa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:docuseal" {...props}></Icon>
