<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbncpjb3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hbncpjb3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:eye-filled" {...props}></Icon>
