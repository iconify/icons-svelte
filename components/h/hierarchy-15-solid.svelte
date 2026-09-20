<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u19doiuhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="u19doiuhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:hierarchy-15-solid" {...props}></Icon>
