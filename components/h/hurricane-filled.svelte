<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fme7b6pkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fme7b6pkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:hurricane-filled" {...props}></Icon>
