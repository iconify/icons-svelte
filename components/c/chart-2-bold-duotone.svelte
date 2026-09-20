<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l6bpllbml.css';
import '../../css/v/v-fqn9o9b.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/b/b0rzzdbxc.css';
import '../../css/a/a_egs8b1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l6bpllbml"/><path class="v-fqn9o9b"/><g class="mc2zb0bvp"><path class="b0rzzdbxc"/><path class="a_egs8b1e"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chart-2-bold-duotone" {...props}></Icon>
