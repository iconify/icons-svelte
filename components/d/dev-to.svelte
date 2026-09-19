<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h909xs_ob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h909xs_ob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:dev-to" {...props}></Icon>
