<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5gtv3biq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q5gtv3biq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-vertical-center-fill" {...props}></Icon>
