<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmw8fw_wo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="nmw8fw_wo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:circle" {...props}></Icon>
