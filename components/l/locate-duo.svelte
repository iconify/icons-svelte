<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7jdrob8h.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/z/zebndbubb.css';
import '../../css/q/q9-8gobaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary z7jdrob8h"/><g class="dt0cm9dhy primary"><circle class="zebndbubb"/><path class="q9-8gobaf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:locate-duo" {...props}></Icon>
