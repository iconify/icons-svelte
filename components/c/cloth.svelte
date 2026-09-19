<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd-_1dbee.css';
import '../../css/b/b9s2v5y7q.css';
import '../../css/p/pvjzk9b8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qd-_1dbee"/><path class="b9s2v5y7q"/><path class="pvjzk9b8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:cloth" {...props}></Icon>
