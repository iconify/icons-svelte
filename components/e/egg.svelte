<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/r/rniplklmo.css';
import '../../css/a/a9vmhrz8t.css';
import '../../css/k/kntuwjb7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><circle class="rniplklmo"/><path class="a9vmhrz8t"/><path class="kntuwjb7f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:egg" {...props}></Icon>
