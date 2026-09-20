<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvd1dhbqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gvd1dhbqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-aws" {...props}></Icon>
