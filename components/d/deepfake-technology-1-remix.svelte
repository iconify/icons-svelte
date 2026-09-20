<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eva2sp1dm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="eva2sp1dm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:deepfake-technology-1-remix" {...props}></Icon>
