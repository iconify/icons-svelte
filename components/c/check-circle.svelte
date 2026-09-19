<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptnxqjb4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ptnxqjb4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:check-circle" {...props}></Icon>
