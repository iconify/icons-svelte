<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-nz-qbkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z-nz-qbkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:align-vertical-spacing-outline" {...props}></Icon>
