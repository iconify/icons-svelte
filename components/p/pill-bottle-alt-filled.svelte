<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fb2njdyzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fb2njdyzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pill-bottle-alt-filled" {...props}></Icon>
