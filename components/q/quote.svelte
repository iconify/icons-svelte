<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vte_uebsx.css';
import '../../css/s/s21yl5blf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vte_uebsx"/><path class="s21yl5blf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:quote" {...props}></Icon>
