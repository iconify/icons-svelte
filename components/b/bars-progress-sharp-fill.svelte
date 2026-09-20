<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ez-140r2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ez-140r2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bars-progress-sharp-fill" {...props}></Icon>
