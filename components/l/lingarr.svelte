<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-b8rwb9q.css';
import '../../css/l/llyqf3b8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="o-b8rwb9q"/><path class="llyqf3b8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lingarr" {...props}></Icon>
