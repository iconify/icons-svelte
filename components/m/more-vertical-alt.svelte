<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovae7zbmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovae7zbmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:more-vertical-alt" {...props}></Icon>
