<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgbnv1b-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cgbnv1b-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:gog" {...props}></Icon>
