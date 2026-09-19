<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l925n1bum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l925n1bum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:grogu" {...props}></Icon>
