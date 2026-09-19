<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezlu90ban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ezlu90ban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:google-fill" {...props}></Icon>
