<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp8v_ebqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mp8v_ebqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:ratio-9-16-fill-round" {...props}></Icon>
