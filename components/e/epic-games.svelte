<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fowq36bhd.css';
import '../../css/u/un3nlpbjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fowq36bhd"/><path class="un3nlpbjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:epic-games" {...props}></Icon>
