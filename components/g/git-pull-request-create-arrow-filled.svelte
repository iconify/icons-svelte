<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvs93ubio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mvs93ubio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:git-pull-request-create-arrow-filled" {...props}></Icon>
