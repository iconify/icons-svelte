<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/js7gortqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="js7gortqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-behance" {...props}></Icon>
