<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khtovtb-c.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/ltvz_r8sf.css';
import '../../css/p/p1kdwps6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="khtovtb-c secondary"/><g class="dt0cm9dhy primary"><path class="ltvz_r8sf"/><path class="p1kdwps6m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:apple-duo" {...props}></Icon>
