<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eng12sjsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eng12sjsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ejabberd-dark" {...props}></Icon>
