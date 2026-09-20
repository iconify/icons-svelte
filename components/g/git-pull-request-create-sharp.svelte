<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4tok7p5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t4tok7p5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:git-pull-request-create-sharp" {...props}></Icon>
