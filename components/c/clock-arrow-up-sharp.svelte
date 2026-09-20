<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtiq49-zo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jtiq49-zo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:clock-arrow-up-sharp" {...props}></Icon>
