<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oijo2cuyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oijo2cuyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:message-2" {...props}></Icon>
