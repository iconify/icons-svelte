<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aftq99syt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aftq99syt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:ev-charger-filled" {...props}></Icon>
