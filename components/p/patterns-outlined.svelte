<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tju-24idz.css';
import '../../css/l/lxi39ds5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tju-24idz"/><path class="lxi39ds5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:patterns-outlined" {...props}></Icon>
