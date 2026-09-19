<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/soy-c7b3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="soy-c7b3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:h6" {...props}></Icon>
