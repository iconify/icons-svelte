<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nj3eyr2qo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nj3eyr2qo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:gallery-vertical-end-sharp" {...props}></Icon>
