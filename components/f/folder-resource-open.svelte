<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtmc67bsf.css';
import '../../css/n/n9mzhphii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jtmc67bsf"/><path class="n9mzhphii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-resource-open" {...props}></Icon>
