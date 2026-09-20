<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thlw7vb4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="thlw7vb4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-up-wide-narrow-sharp" {...props}></Icon>
