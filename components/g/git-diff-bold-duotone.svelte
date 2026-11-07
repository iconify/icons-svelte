<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtpeb-edw.css';
import '../../css/l/lv7o27lha.css';
import '../../css/n/n7pyn85wa.css';
import '../../css/p/p03812bxn.css';
import '../../css/m/mnelrmb_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xtpeb-edw"><path class="lv7o27lha"/><path class="n7pyn85wa"/></g><path clip-rule="evenodd" class="p03812bxn"/><path clip-rule="evenodd" class="mnelrmb_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:git-diff-bold-duotone" {...props}></Icon>
