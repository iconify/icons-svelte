<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dypv3-mdc.css';
import '../../css/j/jrywsebcn.css';
import '../../css/e/eoh-kmiad.css';
import '../../css/u/un29wccgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dypv3-mdc"/><g class="jrywsebcn"><path class="eoh-kmiad"/><circle class="un29wccgo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-circleci" {...props}></Icon>
