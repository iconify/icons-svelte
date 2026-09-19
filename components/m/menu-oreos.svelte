<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkl6re2ft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tkl6re2ft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:menu-oreos" {...props}></Icon>
