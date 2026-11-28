<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh9cc6b_f.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/d7ntyebyk.css';
import '../../css/a/a0e2ybb-k.css';
import '../../css/l/l9z_5vbuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gh9cc6b_f secondary"/><g class="dt0cm9dhy primary"><path class="d7ntyebyk"/><path class="a0e2ybb-k"/><path class="l9z_5vbuy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ghost-duo" {...props}></Icon>
