<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glrde1b3i.css';
import '../../css/h/hgi3nccbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="glrde1b3i"/><path class="hgi3nccbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pill-48" {...props}></Icon>
