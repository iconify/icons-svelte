<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hom_x8bcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hom_x8bcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:not-equal" {...props}></Icon>
