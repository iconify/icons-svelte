<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0_0708wb.css';
import '../../css/b/b768ng9cg.css';
import '../../css/t/ttpih3a4n.css';
import '../../css/h/ht2kccogc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j0_0708wb"/><path class="b768ng9cg"/><path class="ttpih3a4n"/><path class="ht2kccogc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:growth-48" {...props}></Icon>
