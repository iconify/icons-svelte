<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhdm0f4my.css';
import '../../css/n/nzkrizz9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jhdm0f4my"/><path clip-rule="evenodd" class="nzkrizz9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mav" {...props}></Icon>
