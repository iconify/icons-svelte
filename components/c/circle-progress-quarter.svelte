<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbr34pbxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nbr34pbxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-progress-quarter" {...props}></Icon>
