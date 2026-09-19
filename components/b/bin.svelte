<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5fec3gku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a5fec3gku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:bin" {...props}></Icon>
