<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mza5crb4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mza5crb4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:formspirng-logo-block" {...props}></Icon>
