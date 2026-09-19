<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocod4qb4r.css';
import '../../css/x/xyfijqb0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ocod4qb4r"/><path class="xyfijqb0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:download-outline" {...props}></Icon>
