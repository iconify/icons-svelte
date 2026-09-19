<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqhxs-bpd.css';
import '../../css/i/i_n518bgj.css';
import '../../css/p/p31v-_b8t.css';
import '../../css/u/uz70800jt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="oqhxs-bpd"/><circle class="i_n518bgj"/><circle class="p31v-_b8t"/><path class="uz70800jt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:heat-map-02" {...props}></Icon>
