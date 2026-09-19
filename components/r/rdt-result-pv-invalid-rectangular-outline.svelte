<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/e20aw1nql.css';
import '../../css/a/awn3z7bzf.css';
import '../../css/c/c2968140u.css';
import '../../css/w/wa65fi0wq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="e20aw1nql"/><path clip-rule="evenodd" class="awn3z7bzf"/><path clip-rule="evenodd" class="c2968140u"/><path class="wa65fi0wq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:rdt-result-pv-invalid-rectangular-outline" {...props}></Icon>
