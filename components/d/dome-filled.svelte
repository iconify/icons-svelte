<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vewqg9b0r.css';
import '../../css/g/gcy3r1rbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vewqg9b0r"/><path class="gcy3r1rbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:dome-filled" {...props}></Icon>
