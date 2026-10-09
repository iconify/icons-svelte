<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvc9z5wej.css';
import '../../css/d/df3f56xlz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gvc9z5wej"/><path class="df3f56xlz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cactus-48-bold" {...props}></Icon>
