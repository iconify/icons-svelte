<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5f709d9b.css';
import '../../css/v/v_nkltqwk.css';
import '../../css/s/s4l69nb0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k5f709d9b"/><path class="v_nkltqwk"/><path class="s4l69nb0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ammeter-20-bold" {...props}></Icon>
