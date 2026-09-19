<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w56591bca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w56591bca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:password-error" {...props}></Icon>
