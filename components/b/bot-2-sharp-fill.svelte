<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awsq1zbxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="awsq1zbxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bot-2-sharp-fill" {...props}></Icon>
