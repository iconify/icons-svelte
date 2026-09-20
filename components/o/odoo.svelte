<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdv1hacji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdv1hacji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:odoo" {...props}></Icon>
