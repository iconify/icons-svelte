<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7ych6b_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y7ych6b_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:mode-light-fill" {...props}></Icon>
