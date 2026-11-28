<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qk0hgq-4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qk0hgq-4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pickaxe-solid" {...props}></Icon>
