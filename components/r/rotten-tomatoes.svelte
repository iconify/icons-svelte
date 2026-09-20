<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oceqrzbjx.css';
import '../../css/p/p2_f0-rsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oceqrzbjx"/><path class="p2_f0-rsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rotten-tomatoes" {...props}></Icon>
