<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_xc6ub8v.css';
import '../../css/u/unxgk-kjr.css';
import '../../css/x/xuokrglbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_xc6ub8v"/><path class="unxgk-kjr"/><path clip-rule="evenodd" class="xuokrglbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:globus-bold" {...props}></Icon>
