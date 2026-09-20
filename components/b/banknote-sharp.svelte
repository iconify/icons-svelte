<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtr39ob9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mtr39ob9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:banknote-sharp" {...props}></Icon>
