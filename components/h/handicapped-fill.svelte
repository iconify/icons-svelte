<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erv20k74w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="erv20k74w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:handicapped-fill" {...props}></Icon>
