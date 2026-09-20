<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohne5abyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ohne5abyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:button-fast-forward-2" {...props}></Icon>
