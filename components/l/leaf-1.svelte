<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szenc4b2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="szenc4b2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:leaf-1" {...props}></Icon>
