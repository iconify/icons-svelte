<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qocb6tbrl.css';
import '../../css/q/qjh4_sbte.css';
import '../../css/a/ak1se0blo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><circle class="qocb6tbrl"/><circle class="qjh4_sbte"/><path class="ak1se0blo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:cookie-filled" {...props}></Icon>
