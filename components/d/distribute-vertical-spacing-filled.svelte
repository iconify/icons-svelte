<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgds8ynox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kgds8ynox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:distribute-vertical-spacing-filled" {...props}></Icon>
