<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcuvwqb2g.css';
import '../../css/p/p9m8an89s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rcuvwqb2g"/><path class="p9m8an89s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:desertification-48-bold" {...props}></Icon>
