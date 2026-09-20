<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqzrj90_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqzrj90_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:align-center-v" {...props}></Icon>
