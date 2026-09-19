<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/ir4y4fk6l.css';
import '../../css/m/md286fbip.css';
import '../../css/e/enbvbgbfd.css';
import '../../css/r/r9mxuugrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle class="ir4y4fk6l"/><g class="md286fbip"><path class="enbvbgbfd"/><path class="r9mxuugrk"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:meetone" {...props}></Icon>
