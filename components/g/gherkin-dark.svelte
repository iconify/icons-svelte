<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zdw9dcb7o.css';
import '../../css/l/l85b475qg.css';
import '../../css/a/apqxg2b3t.css';
import '../../css/k/k-nql8bba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="ft5dv1b6b"><rect class="zdw9dcb7o"/><path clip-rule="evenodd" class="l85b475qg"/><path class="apqxg2b3t"/><path clip-rule="evenodd" class="k-nql8bba"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="skill-icons:gherkin-dark" {...props}></Icon>
