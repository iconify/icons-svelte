<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otra1mb_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="otra1mb_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panel-bottom-close-fill" {...props}></Icon>
