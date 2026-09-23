<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shqdbd5id.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="shqdbd5id"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:equal-sharp" {...props}></Icon>
