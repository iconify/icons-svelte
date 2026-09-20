<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b68rb-b3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b68rb-b3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:return" {...props}></Icon>
