<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8c63piap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x8c63piap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:align-top-outline" {...props}></Icon>
