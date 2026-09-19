<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lo6-b-g-q.css';
import '../../css/u/ug9pg4zkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":24};
const content = `<path class="lo6-b-g-q"/><path class="ug9pg4zkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:paralysis-disability" {...props}></Icon>
