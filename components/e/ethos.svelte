<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nkj-c5bmo.css';
import '../../css/m/md286fbip.css';
import '../../css/q/qz8pqxbrv.css';
import '../../css/r/r60l57pvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle class="nkj-c5bmo"/><g class="md286fbip"><path class="qz8pqxbrv"/><path class="r60l57pvp"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:ethos" {...props}></Icon>
