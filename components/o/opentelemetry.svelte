<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1_0rk7fh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s1_0rk7fh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:opentelemetry" {...props}></Icon>
