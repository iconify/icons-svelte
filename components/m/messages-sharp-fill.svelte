<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htv5wib5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="htv5wib5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:messages-sharp-fill" {...props}></Icon>
