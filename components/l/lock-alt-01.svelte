<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz0dibbrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gz0dibbrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:lock-alt-01" {...props}></Icon>
