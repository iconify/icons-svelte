<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_0wasj-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_0wasj-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:pool-salinty" {...props}></Icon>
