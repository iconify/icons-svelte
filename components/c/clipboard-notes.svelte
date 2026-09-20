<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utd3f6fhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="utd3f6fhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:clipboard-notes" {...props}></Icon>
