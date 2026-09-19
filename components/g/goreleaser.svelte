<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tm0z6iaql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":391,"height":512};
const content = `<path class="tm0z6iaql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:goreleaser" {...props}></Icon>
