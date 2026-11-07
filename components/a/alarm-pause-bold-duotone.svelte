<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6cqcqlkv.css';
import '../../css/x/x4wr5cbdj.css';
import '../../css/m/m_0p6qboy.css';
import '../../css/k/kube8drda.css';
import '../../css/j/jf1pbcbud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v6cqcqlkv"/><path class="x4wr5cbdj"/><path class="m_0p6qboy"/><path class="kube8drda"/><path class="jf1pbcbud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:alarm-pause-bold-duotone" {...props}></Icon>
