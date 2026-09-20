<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iia8adc_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iia8adc_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:git-branch-check-24" {...props}></Icon>
