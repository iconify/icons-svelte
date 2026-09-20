<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l29pplbre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l29pplbre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:chef-toque-hat-remix" {...props}></Icon>
