<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mazpctb5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mazpctb5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="doodle-icons:list" {...props}></Icon>
