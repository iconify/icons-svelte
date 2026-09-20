<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bebc3s2zk.css';
import '../../css/w/whljx5b0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bebc3s2zk"/><path class="whljx5b0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:playhouse" {...props}></Icon>
