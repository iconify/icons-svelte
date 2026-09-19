<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sc4o63boo.css';
import '../../css/m/md286fbip.css';
import '../../css/v/v1ap4y4nx.css';
import '../../css/g/gyuj_8bfe.css';
import '../../css/j/j1jb155zg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle class="sc4o63boo"/><g class="md286fbip"><path class="v1ap4y4nx"/><path class="gyuj_8bfe"/><path class="j1jb155zg"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:emc2" {...props}></Icon>
