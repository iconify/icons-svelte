<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhsmtt9-j.css';
import '../../css/f/f_0sarbla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qhsmtt9-j"/><path class="f_0sarbla ouiIcon__fillSecondary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:ml-data-visualizer" {...props}></Icon>
