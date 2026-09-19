<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/m9gp5lbxe.css';
import '../../css/u/u_85dibrn.css';
import '../../css/f/fhnpiywoi.css';
import '../../css/e/e5wvorq1u.css';
import '../../css/a/aqwmdacie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><ellipse transform="rotate(-57.793 22.42 7.685)" class="m9gp5lbxe"/><path clip-rule="evenodd" class="u_85dibrn"/><path class="fhnpiywoi"/><path class="e5wvorq1u"/><path class="aqwmdacie"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:billed-cap" {...props}></Icon>
