<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cr3aoqrys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cr3aoqrys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:goplay" {...props}></Icon>
