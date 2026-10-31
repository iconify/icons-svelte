<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kolhlm-_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kolhlm-_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:margin-vertical-filled" {...props}></Icon>
