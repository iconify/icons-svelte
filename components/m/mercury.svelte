<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wszp3tskv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":24};
const content = `<path class="wszp3tskv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:mercury" {...props}></Icon>
