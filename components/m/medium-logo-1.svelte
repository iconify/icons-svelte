<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qa9n4tmlw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qa9n4tmlw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:medium-logo-1" {...props}></Icon>
