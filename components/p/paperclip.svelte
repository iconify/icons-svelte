<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lj4vy298y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lj4vy298y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:paperclip" {...props}></Icon>
