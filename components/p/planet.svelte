<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/h/hwsal5q-o.css';
import '../../css/c/crnr6-62j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><circle class="hwsal5q-o"/><path class="crnr6-62j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:planet" {...props}></Icon>
