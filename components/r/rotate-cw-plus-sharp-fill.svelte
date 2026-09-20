<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eql839oef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eql839oef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:rotate-cw-plus-sharp-fill" {...props}></Icon>
