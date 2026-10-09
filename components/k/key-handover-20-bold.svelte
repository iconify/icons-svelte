<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eab0y1u-b.css';
import '../../css/d/daaedus6x.css';
import '../../css/a/a8vq56b-f.css';
import '../../css/q/qfnoa7bmf.css';
import '../../css/q/q85_wabhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="eab0y1u-b"/><path class="daaedus6x"/><path class="a8vq56b-f"/><path class="qfnoa7bmf"/><path class="q85_wabhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:key-handover-20-bold" {...props}></Icon>
