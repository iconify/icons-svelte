<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aym2qd6ln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aym2qd6ln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:envelope-open" {...props}></Icon>
