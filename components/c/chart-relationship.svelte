<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/l/lyhblcbnl.css';
import '../../css/b/b5fqkvbgz.css';
import '../../css/i/i7327t3bx.css';
import '../../css/z/z9shncc0q.css';
import '../../css/t/tt8nogban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="lyhblcbnl"/><circle class="b5fqkvbgz"/><circle class="i7327t3bx"/><circle class="z9shncc0q"/><circle class="tt8nogban"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:chart-relationship" {...props}></Icon>
