<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awsqrmber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="awsqrmber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:announce" {...props}></Icon>
