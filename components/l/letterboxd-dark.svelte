<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kij9dgb5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kij9dgb5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:letterboxd-dark" {...props}></Icon>
