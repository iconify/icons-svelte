<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6jpqp12d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="i6jpqp12d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:doc-person-fill" {...props}></Icon>
