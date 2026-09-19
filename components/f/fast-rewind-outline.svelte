<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yr13r5e0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yr13r5e0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:fast-rewind-outline" {...props}></Icon>
