<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whrhf5bry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="whrhf5bry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:lightbulb" {...props}></Icon>
