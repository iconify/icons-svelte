<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/en88-6cnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="en88-6cnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:ghost-4-fill" {...props}></Icon>
