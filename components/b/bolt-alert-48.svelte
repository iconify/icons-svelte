<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/em933ob1r.css';
import '../../css/b/bxzxb8v8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="em933ob1r"/><path class="bxzxb8v8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bolt-alert-48" {...props}></Icon>
