<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr55nlbza.css';
import '../../css/n/n79xfpb3k.css';
import '../../css/b/b65gtabis.css';
import '../../css/y/yyvrhuu2d.css';
import '../../css/j/jyufl3bad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="tr55nlbza"/><path class="n79xfpb3k"/><path class="b65gtabis"/><circle class="yyvrhuu2d"/><path class="jyufl3bad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cics-transaction-server-zos" {...props}></Icon>
