<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dftf9rvck.css';
import '../../css/o/oiq_rmbym.css';
import '../../css/f/f8mguzaok.css';
import '../../css/k/kx65r1-1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="dftf9rvck"/><path class="oiq_rmbym"/><path class="f8mguzaok"/><path class="kx65r1-1e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:atom-light" {...props}></Icon>
