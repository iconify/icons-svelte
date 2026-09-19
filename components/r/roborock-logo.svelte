<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gen1u6ueu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gen1u6ueu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:roborock-logo" {...props}></Icon>
