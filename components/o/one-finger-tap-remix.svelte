<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evkiishdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="evkiishdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:one-finger-tap-remix" {...props}></Icon>
