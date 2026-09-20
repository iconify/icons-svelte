<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2qao1pjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j2qao1pjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-plus-logo-1-solid" {...props}></Icon>
