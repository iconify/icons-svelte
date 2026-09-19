<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7pr4cc1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e7pr4cc1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:model-x-charge" {...props}></Icon>
