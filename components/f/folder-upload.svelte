<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9ev8c_0g.css';
import '../../css/j/jfo5ug-pm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer u9ev8c_0g"/><path class="duoicon-primary-layer jfo5ug-pm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:folder-upload" {...props}></Icon>
