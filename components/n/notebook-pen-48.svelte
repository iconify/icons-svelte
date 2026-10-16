<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3wcsw9-a.css';
import '../../css/c/c05cblb0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w3wcsw9-a"/><path class="c05cblb0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:notebook-pen-48" {...props}></Icon>
