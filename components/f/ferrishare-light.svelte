<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxok5ents.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rxok5ents"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ferrishare-light" {...props}></Icon>
