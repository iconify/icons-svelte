<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nn5o39boe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nn5o39boe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panel-top-open-fill" {...props}></Icon>
