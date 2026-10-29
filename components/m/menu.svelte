<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok-_polxz.css';
import '../../css/a/azxuvfb9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ok-_polxz"/><path class="azxuvfb9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:menu" {...props}></Icon>
