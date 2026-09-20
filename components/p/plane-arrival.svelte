<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hp6uidzaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hp6uidzaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:plane-arrival" {...props}></Icon>
