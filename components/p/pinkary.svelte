<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0noxxbmb.css';
import '../../css/t/tdqmgsk7t.css';
import '../../css/y/y2vg62bil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="s0noxxbmb"/><path class="tdqmgsk7t"/><path class="y2vg62bil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pinkary" {...props}></Icon>
