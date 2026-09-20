<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt7bpi-vr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-6,"top":-2};
const content = `<path class="kt7bpi-vr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:padlock-alt-open" {...props}></Icon>
