<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6-j7ubto.css';
import '../../css/n/njy7e9b_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="v6-j7ubto"/><path class="njy7e9b_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openuem-light" {...props}></Icon>
