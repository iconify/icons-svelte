<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oql7-e3yp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oql7-e3yp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:fireflyiii" {...props}></Icon>
