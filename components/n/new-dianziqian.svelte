<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhzvabbex.css';
import '../../css/q/q3_qw6b8e.css';
import '../../css/s/sdj60ogwn.css';
import '../../css/w/w76jl489n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rhzvabbex"/><path class="q3_qw6b8e"/><path class="sdj60ogwn"/><path class="w76jl489n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:new-dianziqian" {...props}></Icon>
