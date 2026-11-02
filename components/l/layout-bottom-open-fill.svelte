<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utprw0bre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="utprw0bre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-bottom-open-fill" {...props}></Icon>
