<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h909b4b3w.css';
import '../../css/f/fzhx4wbsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h909b4b3w"/><circle class="fzhx4wbsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:image-outline" {...props}></Icon>
