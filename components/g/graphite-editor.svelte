<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7542ra8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s7542ra8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:graphite-editor" {...props}></Icon>
