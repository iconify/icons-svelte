<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-zdqbcgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-zdqbcgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:down-line" {...props}></Icon>
