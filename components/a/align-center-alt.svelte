<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wp_dzibvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wp_dzibvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:align-center-alt" {...props}></Icon>
