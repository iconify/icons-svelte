<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6bb6d7lv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r6bb6d7lv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:doordash-light" {...props}></Icon>
