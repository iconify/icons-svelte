<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkvx44x9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hkvx44x9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:moustache-flat" {...props}></Icon>
