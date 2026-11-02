<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahih2qpzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahih2qpzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-panel-top-line" {...props}></Icon>
