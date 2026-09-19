<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p86nkixdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p86nkixdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:nextcloud" {...props}></Icon>
