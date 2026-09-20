<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drj2odafr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="drj2odafr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:panoramic-screen-solid" {...props}></Icon>
