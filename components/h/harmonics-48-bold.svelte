<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwsn-fblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uwsn-fblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:harmonics-48-bold" {...props}></Icon>
