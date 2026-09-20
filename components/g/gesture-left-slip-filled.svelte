<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ont_ilb1y.css';
import '../../css/u/ua3nsqb7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ont_ilb1y"/><path class="ua3nsqb7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:gesture-left-slip-filled" {...props}></Icon>
