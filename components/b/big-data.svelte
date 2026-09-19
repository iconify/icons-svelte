<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr9eogbfz.css';
import '../../css/g/ggybk-j6x.css';
import '../../css/k/kdlhv-bkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wr9eogbfz"/><path class="ggybk-j6x"/><path class="kdlhv-bkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:big-data" {...props}></Icon>
