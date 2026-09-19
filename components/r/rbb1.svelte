<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6n32bbhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c6n32bbhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:rbb1" {...props}></Icon>
