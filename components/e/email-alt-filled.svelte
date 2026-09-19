<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmth8o4lt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fmth8o4lt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:email-alt-filled" {...props}></Icon>
