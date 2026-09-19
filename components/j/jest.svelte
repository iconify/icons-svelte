<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhb8c01ug.css';
import '../../css/k/ke5zifg1a.css';
import '../../css/b/b1feiqias.css';
import '../../css/k/kppkn-rpw.css';
import '../../css/o/o592z9scf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="hhb8c01ug"><path class="ke5zifg1a"/><path class="b1feiqias"/><path class="kppkn-rpw"/><path class="o592z9scf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:jest" {...props}></Icon>
