<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8fx6xbub.css';
import '../../css/e/e8yq54w-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="z8fx6xbub"/><path class="e8yq54w-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:file-share-2-line" {...props}></Icon>
