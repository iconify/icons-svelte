<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iveanybiz.css';
import '../../css/p/p-qjc1xpf.css';
import '../../css/l/ljxetke2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="iveanybiz"><path class="p-qjc1xpf"/><path class="ljxetke2b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:buck" {...props}></Icon>
