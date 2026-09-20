<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tj5g77b1a.css';
import '../../css/w/w7tjisbup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tj5g77b1a"/><path class="w7tjisbup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-mappings" {...props}></Icon>
