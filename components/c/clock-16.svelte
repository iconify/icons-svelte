<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qccp3wbhy.css';
import '../../css/b/b2tyl1b2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qccp3wbhy"/><path clip-rule="evenodd" class="b2tyl1b2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:clock-16" {...props}></Icon>
