<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/om201sw6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="om201sw6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:dial-pad-finger-2-remix" {...props}></Icon>
