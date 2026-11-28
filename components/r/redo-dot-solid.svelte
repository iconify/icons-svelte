<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anb5yxb5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="anb5yxb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:redo-dot-solid" {...props}></Icon>
