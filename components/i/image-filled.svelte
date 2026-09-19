<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2_rusbks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d2_rusbks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:image-filled" {...props}></Icon>
