<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/migij0m8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="migij0m8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:aspect-ratio-filled" {...props}></Icon>
