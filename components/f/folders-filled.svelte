<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5hklmbye.css';
import '../../css/d/d-1rjbc-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m5hklmbye"/><path class="d-1rjbc-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:folders-filled" {...props}></Icon>
