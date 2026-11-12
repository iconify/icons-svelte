<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iufm3lbgw.css';
import '../../css/i/i8odlzb7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iufm3lbgw"/><path class="i8odlzb7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:raygun-monitoring-dark" {...props}></Icon>
