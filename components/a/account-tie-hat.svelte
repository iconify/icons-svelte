<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3kxumt3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c3kxumt3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-tie-hat" {...props}></Icon>
