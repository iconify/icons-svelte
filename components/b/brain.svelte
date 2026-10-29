<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ja04y-mdn.css';
import '../../css/j/jp7x1moyz.css';
import '../../css/k/kqm0fdb1m.css';
import '../../css/y/ypizcvbor.css';
import '../../css/t/te_bqotob.css';
import '../../css/z/z_qlycb2z.css';
import '../../css/k/kb5d24thf.css';
import '../../css/z/ziai-jbsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ja04y-mdn wm-shadow"/><path class="jp7x1moyz wm-k"/><path class="kqm0fdb1m wm-k"/><path class="wm-k ypizcvbor"/><path class="te_bqotob wm-k"/><path class="wm-k z_qlycb2z"/><path class="kb5d24thf wm-shine"/><path class="wm-a ziai-jbsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-pastel:brain" {...props}></Icon>
