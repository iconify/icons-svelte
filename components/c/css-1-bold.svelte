<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq-dyqsyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eq-dyqsyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:css-1-bold" {...props}></Icon>
