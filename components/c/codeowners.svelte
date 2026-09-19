<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qaiyq5bvp.css';
import '../../css/o/ogar2nbat.css';
import '../../css/r/rxmfttsiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="qaiyq5bvp"><path class="ogar2nbat"/><circle class="rxmfttsiy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:codeowners" {...props}></Icon>
