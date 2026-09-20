<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uogvzbc0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uogvzbc0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clipboard-add-outline" {...props}></Icon>
