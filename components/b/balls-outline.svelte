<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4n-2yb9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z4n-2yb9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:balls-outline" {...props}></Icon>
