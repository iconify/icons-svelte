<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsksru3md.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bsksru3md"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:mirror-horizontally-solid" {...props}></Icon>
