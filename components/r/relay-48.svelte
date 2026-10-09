<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmp2mfr9i.css';
import '../../css/n/nsiiab0ne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zmp2mfr9i"/><path class="nsiiab0ne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:relay-48" {...props}></Icon>
