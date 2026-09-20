<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e06csukwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e06csukwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:alert-line" {...props}></Icon>
