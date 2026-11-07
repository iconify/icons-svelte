<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/a/an1auylmc.css';
import '../../css/r/r_kt-dgff.css';
import '../../css/e/eck4ylbag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="an1auylmc"/><path class="r_kt-dgff"/><path class="eck4ylbag"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hand-heart-linear" {...props}></Icon>
