<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glvlf_bmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="glvlf_bmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:france5" {...props}></Icon>
