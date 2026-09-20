<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkddq-bgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jkddq-bgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:info-small" {...props}></Icon>
