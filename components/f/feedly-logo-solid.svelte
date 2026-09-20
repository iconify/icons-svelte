<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7ktktb9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x7ktktb9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:feedly-logo-solid" {...props}></Icon>
