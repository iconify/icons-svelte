<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzzc3f22t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hzzc3f22t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:arrow-up-line" {...props}></Icon>
