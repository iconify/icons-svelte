<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjy4g2uup.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/h1-ng7sis.css';
import '../../css/q/qz1c6q-lt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary wjy4g2uup"/><g class="dt0cm9dhy primary"><path class="h1-ng7sis"/><path class="qz1c6q-lt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bell-duo" {...props}></Icon>
