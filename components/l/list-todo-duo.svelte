<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zk41hkb_g.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/nerq2brpd.css';
import '../../css/a/afuu0c5kl.css';
import '../../css/s/syl86zr3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary zk41hkb_g"/><g class="dt0cm9dhy primary"><path class="nerq2brpd"/><path class="afuu0c5kl"/><path class="syl86zr3b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:list-todo-duo" {...props}></Icon>
