<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6hbulb-g.css';
import '../../css/t/tcuq2ituc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j6hbulb-g"/><path class="tcuq2ituc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:left-down2" {...props}></Icon>
