<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3hiveb_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="u3hiveb_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:fire-two" {...props}></Icon>
