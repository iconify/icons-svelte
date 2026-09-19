<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ju-byuhch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ju-byuhch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:email-fast-filled" {...props}></Icon>
