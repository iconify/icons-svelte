<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtx1xb55s.css';
import '../../css/w/wfevvhiis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vtx1xb55s"/><path class="wfevvhiis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:message-plus-alt" {...props}></Icon>
