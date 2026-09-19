<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/b/b5qbfpbuf.css';
import '../../css/n/nhvgerb4l.css';
import '../../css/a/a4nuxyb-f.css';
import '../../css/t/tt-7ni6ag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="b5qbfpbuf"/><path class="nhvgerb4l"/><circle class="a4nuxyb-f"/><path class="tt-7ni6ag"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:reverse-withdrawal-02" {...props}></Icon>
