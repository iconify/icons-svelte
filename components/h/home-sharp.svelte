<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlgxmq6ep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hlgxmq6ep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:home-sharp" {...props}></Icon>
