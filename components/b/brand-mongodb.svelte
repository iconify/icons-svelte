<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfyo9m4in.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hfyo9m4in"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-mongodb" {...props}></Icon>
