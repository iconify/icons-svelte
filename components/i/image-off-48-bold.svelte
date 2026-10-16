<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ara_cab0k.css';
import '../../css/o/o6es3ib2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ara_cab0k"/><path class="o6es3ib2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:image-off-48-bold" {...props}></Icon>
