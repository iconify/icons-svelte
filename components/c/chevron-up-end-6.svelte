<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9-tsqbmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="a9-tsqbmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:chevron-up-end-6" {...props}></Icon>
