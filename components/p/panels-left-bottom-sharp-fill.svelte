<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yb4xki1ru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yb4xki1ru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panels-left-bottom-sharp-fill" {...props}></Icon>
