<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uu258tb2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary uu258tb2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chevron-down-duotone" {...props}></Icon>
