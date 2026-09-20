<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3fh60krs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b3fh60krs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:flag-2-broken" {...props}></Icon>
