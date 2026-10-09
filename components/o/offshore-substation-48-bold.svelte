<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awsea6blm.css';
import '../../css/e/e7rwfg02i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="awsea6blm"/><path class="e7rwfg02i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:offshore-substation-48-bold" {...props}></Icon>
