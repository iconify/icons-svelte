<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tg-d9bb-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tg-d9bb-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-down-sharp" {...props}></Icon>
