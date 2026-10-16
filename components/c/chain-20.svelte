<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6mu4cbgx.css';
import '../../css/e/eqj_f_bga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v6mu4cbgx"/><path class="eqj_f_bga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chain-20" {...props}></Icon>
