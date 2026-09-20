<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okyr0-bih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="okyr0-bih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-half-2" {...props}></Icon>
