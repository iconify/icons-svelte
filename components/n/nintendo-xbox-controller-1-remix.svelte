<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz_n6bbyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jz_n6bbyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:nintendo-xbox-controller-1-remix" {...props}></Icon>
