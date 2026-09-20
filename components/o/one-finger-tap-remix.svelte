<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r723k724g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="r723k724g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:one-finger-tap-remix" {...props}></Icon>
