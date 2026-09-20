<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozfl8nbgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ozfl8nbgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-dollar-sign-sharp-fill" {...props}></Icon>
