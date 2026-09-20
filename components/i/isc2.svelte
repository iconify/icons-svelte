<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avt6vcbxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="avt6vcbxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:isc2" {...props}></Icon>
