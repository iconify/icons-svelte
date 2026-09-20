<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pelcyhb6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pelcyhb6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:maya-pyramids-fill" {...props}></Icon>
