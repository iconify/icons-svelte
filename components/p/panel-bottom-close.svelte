<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgkc1nqpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jgkc1nqpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panel-bottom-close" {...props}></Icon>
