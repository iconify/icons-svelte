<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgx0dlr5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vgx0dlr5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:coffe-to-go" {...props}></Icon>
