<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq491_u9m.css';
import '../../css/r/rjc2wjb6s.css';
import '../../css/b/bq3zunblc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wq491_u9m"/><path class="rjc2wjb6s"/><path class="bq3zunblc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:drum-20-bold" {...props}></Icon>
