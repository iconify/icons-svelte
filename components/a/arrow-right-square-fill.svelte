<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovmqfnq7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ovmqfnq7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:arrow-right-square-fill" {...props}></Icon>
