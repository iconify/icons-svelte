<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msi7434ap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="msi7434ap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-up-right" {...props}></Icon>
