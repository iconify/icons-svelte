<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emq9xhbfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="emq9xhbfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:moon-cloud-remix" {...props}></Icon>
