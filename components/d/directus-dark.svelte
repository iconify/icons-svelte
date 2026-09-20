<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awy5dwb7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="awy5dwb7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:directus-dark" {...props}></Icon>
