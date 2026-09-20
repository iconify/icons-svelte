<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjvwrvb1c.css';
import '../../css/j/jobtlp51p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vjvwrvb1c"/><path class="jobtlp51p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:git-pages" {...props}></Icon>
