<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4e1i3bta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4e1i3bta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:database" {...props}></Icon>
