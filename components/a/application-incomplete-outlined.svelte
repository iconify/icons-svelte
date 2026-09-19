<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t683n5mpp.css';
import '../../css/t/tssojcb-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t683n5mpp"/><path class="tssojcb-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:application-incomplete-outlined" {...props}></Icon>
