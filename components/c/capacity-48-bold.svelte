<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-4rqjbfm.css';
import '../../css/a/aw6b_uyup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="t-4rqjbfm"/><path class="aw6b_uyup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:capacity-48-bold" {...props}></Icon>
