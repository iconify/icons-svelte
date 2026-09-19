<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xviqmb0wz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xviqmb0wz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:h4" {...props}></Icon>
