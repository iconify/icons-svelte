<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vx5t9xzug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vx5t9xzug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:copy-sharp" {...props}></Icon>
