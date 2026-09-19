<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/concw1lqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="concw1lqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:bootstrap" {...props}></Icon>
