<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dy2-8fbyk.css';
import '../../css/z/z0vd8mbkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dy2-8fbyk"/><path class="z0vd8mbkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:chevron-up" {...props}></Icon>
