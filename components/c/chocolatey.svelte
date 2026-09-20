<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acjh3nbbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="acjh3nbbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:chocolatey" {...props}></Icon>
