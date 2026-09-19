<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulc-50zkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ulc-50zkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:layer" {...props}></Icon>
