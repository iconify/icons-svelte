<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awsea6blm.css';
import '../../css/o/o9nde9b-c.css';
import '../../css/x/xmrhsdbaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="awsea6blm"/><path class="o9nde9b-c"/><path class="xmrhsdbaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:piston-48-bold" {...props}></Icon>
