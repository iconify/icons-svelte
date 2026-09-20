<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u03gbh6os.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u03gbh6os"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:align-right" {...props}></Icon>
