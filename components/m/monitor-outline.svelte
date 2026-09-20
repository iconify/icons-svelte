<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inh_04poa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="inh_04poa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:monitor-outline" {...props}></Icon>
