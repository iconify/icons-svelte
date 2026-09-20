<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9zlttpcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v9zlttpcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:gallery-thumbnails" {...props}></Icon>
