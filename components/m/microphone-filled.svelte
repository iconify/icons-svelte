<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amefarb4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="amefarb4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:microphone-filled" {...props}></Icon>
