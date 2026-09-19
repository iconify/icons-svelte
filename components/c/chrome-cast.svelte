<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t691w9ufv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t691w9ufv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chrome-cast" {...props}></Icon>
