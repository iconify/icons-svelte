<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/h/heyq2bc2u.css';
import '../../css/m/mrda_3qxu.css';
import '../../css/h/hjjceedbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="heyq2bc2u"/><path class="mrda_3qxu"/><path class="hjjceedbl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:film-roll-02" {...props}></Icon>
