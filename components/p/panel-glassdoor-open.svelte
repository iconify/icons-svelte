<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2z75ia-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e2z75ia-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:panel-glassdoor-open" {...props}></Icon>
