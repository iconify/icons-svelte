<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edpbscfjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="edpbscfjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:ghost-fill" {...props}></Icon>
