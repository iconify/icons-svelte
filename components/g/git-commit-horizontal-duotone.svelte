<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f29fwjbso.css';
import '../../css/j/jyuddqs9y.css';
import '../../css/f/fv37sub-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f29fwjbso"/><path class="jyuddqs9y"/><path class="fv37sub-u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:git-commit-horizontal-duotone" {...props}></Icon>
