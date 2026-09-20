<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjkxsr8pn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sjkxsr8pn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:lucia" {...props}></Icon>
