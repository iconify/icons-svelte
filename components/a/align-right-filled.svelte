<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zi62yk3_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zi62yk3_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:align-right-filled" {...props}></Icon>
