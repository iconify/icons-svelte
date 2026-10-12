<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4iq45b8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x4iq45b8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:git-merge-conflict-filled" {...props}></Icon>
