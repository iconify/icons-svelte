<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvnfzn9zr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lvnfzn9zr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:optopia" {...props}></Icon>
