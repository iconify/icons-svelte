<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb5e2cbax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nb5e2cbax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-11-line" {...props}></Icon>
