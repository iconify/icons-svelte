<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lczf7rbjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lczf7rbjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:keybase" {...props}></Icon>
