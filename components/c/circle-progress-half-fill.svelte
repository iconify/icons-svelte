<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg4ofbcbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jg4ofbcbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-progress-half-fill" {...props}></Icon>
