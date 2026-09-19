<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1xfxt6no.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="j1xfxt6no"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:arrows-maximize" {...props}></Icon>
