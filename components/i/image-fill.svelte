<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/geplj-_un.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="geplj-_un"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:image-fill" {...props}></Icon>
