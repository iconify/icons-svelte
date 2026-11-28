<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/m-7lzdbyj.css';
import '../../css/a/assf6sbkp.css';
import '../../css/u/ua6v0j9ye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="m-7lzdbyj"/><path class="assf6sbkp"/><path class="ua6v0j9ye"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ai-write" {...props}></Icon>
