<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pec08zb3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pec08zb3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:flow-switch" {...props}></Icon>
