<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/c4bw41thd.css';
import '../../css/k/kbtrenb5s.css';
import '../../css/d/dqk3scc2o.css';
import '../../css/q/qk90v_uvm.css';
import '../../css/v/vrwte0oxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="c4bw41thd"/><path clip-rule="evenodd" class="kbtrenb5s"/><path class="dqk3scc2o"/><path class="qk90v_uvm"/><path class="vrwte0oxc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:pharmacy" {...props}></Icon>
