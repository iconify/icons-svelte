<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/roar_qb4z.css';
import '../../css/v/vzih_tb-s.css';
import '../../css/r/rn06_bbzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="roar_qb4z"/><path class="vzih_tb-s"/><path class="rn06_bbzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:folder-lune" {...props}></Icon>
