<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fje0ntbbb.css';
import '../../css/z/zjmdfw3ya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="fje0ntbbb"/><path class="zjmdfw3ya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:omnivore" {...props}></Icon>
