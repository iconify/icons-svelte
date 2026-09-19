<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/r/r2iitdbys.css';
import '../../css/t/tkiz4rbld.css';
import '../../css/s/s2j1gkbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="r2iitdbys"/><path class="tkiz4rbld"/><path class="s2j1gkbik"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:arrow-down-right" {...props}></Icon>
