<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odrrekjno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="odrrekjno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:cardano-ada" {...props}></Icon>
