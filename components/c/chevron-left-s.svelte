<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmx63kvih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qmx63kvih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chevron-left-s" {...props}></Icon>
