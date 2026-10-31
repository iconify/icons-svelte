<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1f5b8moy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a1f5b8moy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:clock-5-round" {...props}></Icon>
