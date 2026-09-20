<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duhnwsbdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duhnwsbdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bug-sharp" {...props}></Icon>
