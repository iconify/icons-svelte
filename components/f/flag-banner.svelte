<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkrb7h_yw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mkrb7h_yw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:flag-banner" {...props}></Icon>
