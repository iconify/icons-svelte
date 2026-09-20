<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2chacc0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y2chacc0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:fontawesome" {...props}></Icon>
