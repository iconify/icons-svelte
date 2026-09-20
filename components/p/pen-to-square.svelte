<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hoyfe3bws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hoyfe3bws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:pen-to-square" {...props}></Icon>
