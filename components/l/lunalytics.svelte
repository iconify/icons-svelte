<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcz9gmb8w.css';
import '../../css/v/vi3jb3b5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wcz9gmb8w"/><path class="vi3jb3b5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lunalytics" {...props}></Icon>
