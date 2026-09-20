<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4psdzbtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l4psdzbtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:grip-vertical-sharp-duotone" {...props}></Icon>
