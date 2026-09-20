<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9-_0pbhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-7,"top":-2};
const content = `<path class="u9-_0pbhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:bottle" {...props}></Icon>
