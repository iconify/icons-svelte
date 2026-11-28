<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x72m91b6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary x72m91b6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:focus-duotone" {...props}></Icon>
