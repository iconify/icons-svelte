<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz2byabdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":768};
const content = `<path class="nz2byabdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:cassette" {...props}></Icon>
