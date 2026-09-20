<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i18x_pb8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i18x_pb8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-tether" {...props}></Icon>
