<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct7v-bboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ct7v-bboa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:equal-approximately-sharp-fill" {...props}></Icon>
