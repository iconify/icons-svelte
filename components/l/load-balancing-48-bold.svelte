<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo0xevpbl.css';
import '../../css/b/b9o66unef.css';
import '../../css/z/zw7micchl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="eo0xevpbl"/><path class="b9o66unef"/><path class="zw7micchl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:load-balancing-48-bold" {...props}></Icon>
