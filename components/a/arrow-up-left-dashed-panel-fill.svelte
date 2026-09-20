<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdv40tb3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdv40tb3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-up-left-dashed-panel-fill" {...props}></Icon>
