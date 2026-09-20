<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5act16ap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e5act16ap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:layout-left-2-line" {...props}></Icon>
