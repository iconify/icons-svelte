<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eie4uo28e.css';
import '../../css/n/n_2ctgbqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eie4uo28e"/><path class="n_2ctgbqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-upload-outline" {...props}></Icon>
