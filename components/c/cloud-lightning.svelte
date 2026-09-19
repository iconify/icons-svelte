<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aztr-g88x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aztr-g88x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cloud-lightning" {...props}></Icon>
