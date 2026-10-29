<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/s/srev3-blk.css';
import '../../css/o/ob4hknlne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="n1lsf0bnc"><path class="srev3-blk"/><path class="ob4hknlne wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:layout-list-solid" {...props}></Icon>
