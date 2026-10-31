<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sl_fohx5d.css';
import '../../css/s/scv9d7bem.css';
import '../../css/a/a0o4ub92n.css';
import '../../css/u/ucogdbb3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="sl_fohx5d"/><path class="scv9d7bem"/><path class="a0o4ub92n"/><path class="ucogdbb3g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:database-cog-duotone" {...props}></Icon>
