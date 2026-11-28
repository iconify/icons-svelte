<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dy7albcqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dy7albcqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:face-surprised" {...props}></Icon>
