<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n97hkd6ve.css';
import '../../css/f/f_ua4blav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n97hkd6ve secondary"/><path class="f_ua4blav primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-big-up-duo" {...props}></Icon>
