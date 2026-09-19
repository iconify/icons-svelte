<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/q/q5bvs4b8s.css';
import '../../css/x/xejwnnbvm.css';
import '../../css/q/q2t5n-b0f.css';
import '../../css/a/ac6x5rb4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="q5bvs4b8s"/><path class="xejwnnbvm"/><path class="q2t5n-b0f"/><path class="ac6x5rb4v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bus-02" {...props}></Icon>
