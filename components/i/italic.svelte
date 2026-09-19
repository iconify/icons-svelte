<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agla4pb3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="agla4pb3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:italic" {...props}></Icon>
