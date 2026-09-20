<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljv9kz7ks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="ljv9kz7ks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:pet-store" {...props}></Icon>
