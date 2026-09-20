<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hradzg3vi.css';
import '../../css/n/norpj8pcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hradzg3vi"/><path class="norpj8pcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:raygun-monitoring-dark" {...props}></Icon>
