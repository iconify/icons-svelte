<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm81ozbmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vm81ozbmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:observable" {...props}></Icon>
