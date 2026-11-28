<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyglkvb0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hyglkvb0z primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:asterisk-duotone" {...props}></Icon>
