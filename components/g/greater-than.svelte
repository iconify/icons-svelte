<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecjoy0h7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ecjoy0h7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:greater-than" {...props}></Icon>
