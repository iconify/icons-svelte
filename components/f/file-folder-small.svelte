<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ah31_6brh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ah31_6brh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:file-folder-small" {...props}></Icon>
