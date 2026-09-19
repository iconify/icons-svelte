<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rev1gzb0u.css';
import '../../css/e/etgq1od9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rev1gzb0u"/><path class="etgq1od9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:mouth" {...props}></Icon>
