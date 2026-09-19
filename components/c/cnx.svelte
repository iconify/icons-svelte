<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/d/dg4d_poch.css';
import '../../css/n/n1mjunbsu.css';
import '../../css/k/k5darrm3j.css';
import '../../css/p/p6g_r5ogo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="bi12bsetm"><circle class="dg4d_poch"/><g class="n1mjunbsu"><path class="k5darrm3j"/><path class="p6g_r5ogo"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:cnx" {...props}></Icon>
