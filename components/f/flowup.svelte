<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksiwmgbtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":833};
const content = `<path class="ksiwmgbtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:flowup" {...props}></Icon>
