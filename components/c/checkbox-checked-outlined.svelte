<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/p/pu3c7wbmz.css';
import '../../css/y/y8nllnb_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="checkbox-checked-outlined"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="pu3c7wbmz"/><path class="y8nllnb_t"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:checkbox-checked-outlined" {...props}></Icon>
