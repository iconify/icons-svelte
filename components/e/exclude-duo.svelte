<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9p-jgu8o.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/vthn-7s8a.css';
import '../../css/j/jg8edzpch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c9p-jgu8o secondary"/><g class="dt0cm9dhy primary"><path class="vthn-7s8a"/><path class="jg8edzpch"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:exclude-duo" {...props}></Icon>
