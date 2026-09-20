<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlvzzwmpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hlvzzwmpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:expand-dashed-down-left-sharp" {...props}></Icon>
