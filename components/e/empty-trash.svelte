<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hakimgbod.css';
import '../../css/p/p9b78ab8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hakimgbod"/><path class="p9b78ab8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:empty-trash" {...props}></Icon>
