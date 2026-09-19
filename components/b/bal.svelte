<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/amzs62l_r.css';
import '../../css/m/md286fbip.css';
import '../../css/p/pthgwib3v.css';
import '../../css/n/nodvywbpm.css';
import '../../css/j/jblli5bgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle class="amzs62l_r"/><g class="md286fbip"><path class="pthgwib3v"/><path class="nodvywbpm"/><path class="jblli5bgd"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:bal" {...props}></Icon>
