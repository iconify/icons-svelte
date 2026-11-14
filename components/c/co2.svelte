<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_em85nnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_em85nnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:co2" {...props}></Icon>
