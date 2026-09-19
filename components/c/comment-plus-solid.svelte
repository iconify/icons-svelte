<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2x8iab1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m2x8iab1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:comment-plus-solid" {...props}></Icon>
