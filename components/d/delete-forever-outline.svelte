<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gq8pe9b6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gq8pe9b6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:delete-forever-outline" {...props}></Icon>
