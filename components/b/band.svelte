<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/momxgpb6o.css';
import '../../css/m/md286fbip.css';
import '../../css/i/i8nlo91al.css';
import '../../css/x/xlqm4ibmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle class="momxgpb6o"/><g class="md286fbip"><path class="i8nlo91al"/><path class="xlqm4ibmx"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:band" {...props}></Icon>
