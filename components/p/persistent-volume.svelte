<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3ckgebfq.css';
import '../../css/x/xda2a_cpg.css';
import '../../css/q/qo15eky2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n3ckgebfq"/><path class="xda2a_cpg"/><circle class="qo15eky2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:persistent-volume" {...props}></Icon>
