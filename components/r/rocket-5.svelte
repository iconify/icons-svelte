<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apmey5ikj.css';
import '../../css/r/rn5l7u0ji.css';
import '../../css/q/qmx_0jbvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="apmey5ikj"/><path class="rn5l7u0ji"/><path class="qmx_0jbvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:rocket-5" {...props}></Icon>
