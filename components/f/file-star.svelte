<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/y/y9mzy0bvl.css';
import '../../css/h/hji4qyb_f.css';
import '../../css/c/cr7gqybwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="y9mzy0bvl"/><path class="hji4qyb_f"/><path class="cr7gqybwy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:file-star" {...props}></Icon>
