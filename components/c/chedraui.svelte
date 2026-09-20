<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eom6zw58a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eom6zw58a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:chedraui" {...props}></Icon>
