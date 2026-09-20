<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv9g8bbni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nv9g8bbni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:googletasks" {...props}></Icon>
