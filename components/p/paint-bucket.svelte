<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/i66nlzbsu.css';
import '../../css/c/cai4gqkcy.css';
import '../../css/c/cu1zsc2zh.css';
import '../../css/l/lg3m63ztu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="i66nlzbsu"/><path class="cai4gqkcy"/><path class="cu1zsc2zh"/><path class="lg3m63ztu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:paint-bucket" {...props}></Icon>
