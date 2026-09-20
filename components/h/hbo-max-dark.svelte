<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0wvtc8gu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o0wvtc8gu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hbo-max-dark" {...props}></Icon>
