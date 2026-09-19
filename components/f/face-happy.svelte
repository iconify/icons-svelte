<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5g15mqar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x5g15mqar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:face-happy" {...props}></Icon>
