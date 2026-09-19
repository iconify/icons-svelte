<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7a0u441t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a7a0u441t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ezviz" {...props}></Icon>
