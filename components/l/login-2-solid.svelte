<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9oom-12u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n9oom-12u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:login-2-solid" {...props}></Icon>
