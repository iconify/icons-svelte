<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o14vgl1ja.css';
import '../../css/s/s_w1wxr_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o14vgl1ja"/><path clip-rule="evenodd" class="s_w1wxr_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:info-16" {...props}></Icon>
