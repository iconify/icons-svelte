<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zl86_db2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zl86_db2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:cadillac" {...props}></Icon>
