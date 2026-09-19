<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_i-_ub5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r_i-_ub5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:contact-lenses-outline-24px" {...props}></Icon>
