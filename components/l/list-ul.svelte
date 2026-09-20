<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0fc02bet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f0fc02bet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:list-ul" {...props}></Icon>
