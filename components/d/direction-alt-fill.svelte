<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g54l429zx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g54l429zx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:direction-alt-fill" {...props}></Icon>
