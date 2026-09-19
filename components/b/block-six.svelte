<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdsxwd93f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fdsxwd93f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:block-six" {...props}></Icon>
