<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o21yy6bel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="o21yy6bel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="brandico:bandcamp" {...props}></Icon>
