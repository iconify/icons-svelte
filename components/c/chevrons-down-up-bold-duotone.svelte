<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtpeb-edw.css';
import '../../css/x/xp2wd6b7o.css';
import '../../css/t/ti79v0bxi.css';
import '../../css/h/hqsxmzcag.css';
import '../../css/a/afqh91xni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xtpeb-edw"><path class="xp2wd6b7o"/><path class="ti79v0bxi"/></g><path class="hqsxmzcag"/><path class="afqh91xni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chevrons-down-up-bold-duotone" {...props}></Icon>
