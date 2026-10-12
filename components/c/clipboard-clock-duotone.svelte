<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b2hl1gbca.css';
import '../../css/o/opzqht43q.css';
import '../../css/m/mw2-7wb7w.css';
import '../../css/e/emoy9fbht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="b2hl1gbca"/><path class="opzqht43q"/><path class="mw2-7wb7w"/><path class="emoy9fbht"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:clipboard-clock-duotone" {...props}></Icon>
