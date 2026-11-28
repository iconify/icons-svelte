<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4uqq4buf.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/fd0uewd8f.css';
import '../../css/q/q940tbb7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary z4uqq4buf"/><g class="dt0cm9dhy primary"><path class="fd0uewd8f"/><path class="q940tbb7t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:castle-duo" {...props}></Icon>
