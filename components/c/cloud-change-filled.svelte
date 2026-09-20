<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcqmj_blq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jcqmj_blq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:cloud-change-filled" {...props}></Icon>
