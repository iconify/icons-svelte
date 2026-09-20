<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-yw3ub1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b-yw3ub1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:exclamation-square-fill" {...props}></Icon>
