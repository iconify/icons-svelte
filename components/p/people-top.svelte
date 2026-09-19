<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4g7cd22t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a4g7cd22t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:people-top" {...props}></Icon>
