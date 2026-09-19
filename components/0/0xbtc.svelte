<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/i/i18k795dc.css';
import '../../css/m/md286fbip.css';
import '../../css/a/aildwlbyw.css';
import '../../css/g/gzs6bzqtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="bi12bsetm"><circle class="i18k795dc"/><g class="md286fbip"><path class="aildwlbyw"/><path class="gzs6bzqtu"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:0xbtc" {...props}></Icon>
