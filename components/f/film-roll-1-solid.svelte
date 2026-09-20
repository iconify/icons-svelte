<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/peddjfbfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="peddjfbfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:film-roll-1-solid" {...props}></Icon>
