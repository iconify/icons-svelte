<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbf3dqbzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qbf3dqbzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:alarm-filled" {...props}></Icon>
