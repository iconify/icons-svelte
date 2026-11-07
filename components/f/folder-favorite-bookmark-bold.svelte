<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_n90ytqs.css';
import '../../css/z/zwya4wbyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u_n90ytqs"/><path class="zwya4wbyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-favorite-bookmark-bold" {...props}></Icon>
