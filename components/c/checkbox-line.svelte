<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x54q-ebok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x54q-ebok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:checkbox-line" {...props}></Icon>
