<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uovlzzb5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uovlzzb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:beer" {...props}></Icon>
