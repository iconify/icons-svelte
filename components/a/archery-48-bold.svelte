<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1xo7-eok.css';
import '../../css/r/rr_64kzjn.css';
import '../../css/l/lxxd1u4jy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="v1xo7-eok"/><path class="rr_64kzjn"/><path class="lxxd1u4jy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:archery-48-bold" {...props}></Icon>
