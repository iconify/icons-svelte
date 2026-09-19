<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj0jtsbyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jj0jtsbyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:dollar-circle-solid" {...props}></Icon>
