<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5p-meb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g5p-meb9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:nx" {...props}></Icon>
