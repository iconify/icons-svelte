<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmqj-lcmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nmqj-lcmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:owncloud-dark" {...props}></Icon>
