<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwi27ebxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iwi27ebxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:bag-add-outline" {...props}></Icon>
