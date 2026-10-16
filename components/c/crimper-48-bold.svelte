<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/al8t810di.css';
import '../../css/x/xtbtl4t9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="al8t810di"/><path class="xtbtl4t9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crimper-48-bold" {...props}></Icon>
