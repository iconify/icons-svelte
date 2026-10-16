<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k23_kvbcb.css';
import '../../css/b/b22tnbb6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k23_kvbcb"/><path class="b22tnbb6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:paper-mill-48" {...props}></Icon>
