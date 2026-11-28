<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kup2jqy7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kup2jqy7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bear-solid" {...props}></Icon>
