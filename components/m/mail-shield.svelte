<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/vqntw0b8l.css';
import '../../css/o/or41fg4zb.css';
import '../../css/y/ym2hmp47k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="vqntw0b8l"/><path class="or41fg4zb"/><path class="ym2hmp47k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:mail-shield" {...props}></Icon>
