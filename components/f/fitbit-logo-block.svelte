<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nam5eh0cu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nam5eh0cu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:fitbit-logo-block" {...props}></Icon>
