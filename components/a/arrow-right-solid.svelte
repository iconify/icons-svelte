<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cme-xj5sm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cme-xj5sm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:arrow-right-solid" {...props}></Icon>
