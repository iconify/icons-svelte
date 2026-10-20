<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdwcq3bta.css';
import '../../css/s/s865abbii.css';
import '../../css/a/ame6s9x0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bdwcq3bta"/><path class="s865abbii"/><path class="ame6s9x0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flask-48" {...props}></Icon>
