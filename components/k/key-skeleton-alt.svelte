<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzlo_6bye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mzlo_6bye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:key-skeleton-alt" {...props}></Icon>
