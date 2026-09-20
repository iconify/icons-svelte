<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txvyr0b6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="txvyr0b6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:10-plus" {...props}></Icon>
