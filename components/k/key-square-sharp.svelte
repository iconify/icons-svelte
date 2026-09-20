<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-irwm9cw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-irwm9cw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:key-square-sharp" {...props}></Icon>
