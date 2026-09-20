<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9n1396-x.css';
import '../../css/g/g-e3hmm2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b9n1396-x"/><path class="g-e3hmm2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:frappe-insights" {...props}></Icon>
