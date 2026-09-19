<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/ty83eqb9r.css';
import '../../css/m/md286fbip.css';
import '../../css/x/x-nm-pbbn.css';
import '../../css/p/pqll-jyub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle class="ty83eqb9r"/><g class="md286fbip"><path class="x-nm-pbbn"/><path class="pqll-jyub"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:dth" {...props}></Icon>
