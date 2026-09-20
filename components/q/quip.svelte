<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to-9a9geg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="to-9a9geg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:quip" {...props}></Icon>
