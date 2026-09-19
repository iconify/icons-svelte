<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/b/btc0ci6jt.css';
import '../../css/n/n9i8cmbmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="power-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="btc0ci6jt"/><path class="n9i8cmbmc"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:power-outline" {...props}></Icon>
