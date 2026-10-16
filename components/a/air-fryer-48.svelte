<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-5qdfbve.css';
import '../../css/a/ammtthdlg.css';
import '../../css/b/bd01pac2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="u-5qdfbve"/><path class="ammtthdlg"/><path class="bd01pac2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:air-fryer-48" {...props}></Icon>
