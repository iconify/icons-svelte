<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/njo0cebfl.css';
import '../../css/k/kjwe9db2a.css';
import '../../css/g/g7d-yysdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><rect class="njo0cebfl"/><path class="kjwe9db2a"/><rect transform="rotate(90 15 29)" class="g7d-yysdb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:painted-screen" {...props}></Icon>
