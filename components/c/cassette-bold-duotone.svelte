<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/geoim1bqf.css';
import '../../css/g/gj0fhibpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="geoim1bqf"/><path clip-rule="evenodd" class="gj0fhibpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cassette-bold-duotone" {...props}></Icon>
