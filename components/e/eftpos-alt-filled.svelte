<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in57ir3hv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="in57ir3hv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:eftpos-alt-filled" {...props}></Icon>
