<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-k-i5ydk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l-k-i5ydk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:option-key-48" {...props}></Icon>
