<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-3jbebss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-3jbebss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:arrow-up-solid" {...props}></Icon>
