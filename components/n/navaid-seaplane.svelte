<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0y7ydbid.css';
import '../../css/c/c4j2u85_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i0y7ydbid"/><path class="c4j2u85_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:navaid-seaplane" {...props}></Icon>
