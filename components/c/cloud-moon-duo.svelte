<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brujerrhn.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/apwpyxbph.css';
import '../../css/b/by47lokjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="brujerrhn secondary"/><g class="dt0cm9dhy primary"><path class="apwpyxbph"/><path class="by47lokjy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cloud-moon-duo" {...props}></Icon>
