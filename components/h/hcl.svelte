<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7tdrk9ta.css';
import '../../css/g/g3yfe1b-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u7tdrk9ta"/><path class="g3yfe1b-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:hcl" {...props}></Icon>
