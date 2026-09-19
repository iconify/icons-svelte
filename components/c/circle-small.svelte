<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orle7obbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="orle7obbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:circle-small" {...props}></Icon>
