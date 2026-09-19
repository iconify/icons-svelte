<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyd5-obni.css';
import '../../css/t/th32pl67c.css';
import '../../css/q/q_2n7obtj.css';
import '../../css/z/zvgjxlbcx.css';
import '../../css/b/betwnjbtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wyd5-obni"/><path class="th32pl67c"/><path class="q_2n7obtj"/><path class="zvgjxlbcx"/><path class="betwnjbtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:cloud-domains" {...props}></Icon>
