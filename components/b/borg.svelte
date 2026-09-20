<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b774deb7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b774deb7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:borg" {...props}></Icon>
