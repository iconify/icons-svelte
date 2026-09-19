<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/a_e628bht.css';
import '../../css/m/md286fbip.css';
import '../../css/e/eoq7jqbkh.css';
import '../../css/u/uqman41yd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle class="a_e628bht"/><g class="md286fbip"><path class="eoq7jqbkh"/><path class="uqman41yd"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:knc" {...props}></Icon>
