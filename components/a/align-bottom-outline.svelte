<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edaszvb7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="edaszvb7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:align-bottom-outline" {...props}></Icon>
