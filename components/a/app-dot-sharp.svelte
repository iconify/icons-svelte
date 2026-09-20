<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_dup352m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l_dup352m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:app-dot-sharp" {...props}></Icon>
