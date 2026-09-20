<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_6n9bb-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_6n9bb-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-progress-half-sharp-fill" {...props}></Icon>
