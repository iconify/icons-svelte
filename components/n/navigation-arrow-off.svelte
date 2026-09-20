<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cv0mh3bvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cv0mh3bvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:navigation-arrow-off" {...props}></Icon>
