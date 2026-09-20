<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc6mpdb9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4.5,"top":-2};
const content = `<path class="xc6mpdb9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:pinterest" {...props}></Icon>
