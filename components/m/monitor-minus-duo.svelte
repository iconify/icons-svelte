<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k75jqw9vz.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/bkhpw8bej.css';
import '../../css/i/izggtwq7w.css';
import '../../css/y/yyv159b9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k75jqw9vz secondary"/><g class="dt0cm9dhy primary"><path class="bkhpw8bej"/><path class="izggtwq7w"/><path class="yyv159b9n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:monitor-minus-duo" {...props}></Icon>
