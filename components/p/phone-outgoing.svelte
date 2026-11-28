<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za3kuebvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="za3kuebvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:phone-outgoing" {...props}></Icon>
