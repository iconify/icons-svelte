<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aw5i6eh9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="aw5i6eh9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:bell-remix" {...props}></Icon>
