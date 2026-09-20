<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qg-d_6rce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qg-d_6rce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:lmstudio" {...props}></Icon>
