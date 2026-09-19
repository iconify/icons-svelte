<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hi_3yte4a.css';
import '../../css/q/qqbau88aq.css';
import '../../css/a/ag75s1cpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="hi_3yte4a"/><path clip-rule="evenodd" class="qqbau88aq"/><path class="ag75s1cpg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:dairy-outline" {...props}></Icon>
