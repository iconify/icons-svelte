<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvbbl6ipz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-1.5,"top":-2};
const content = `<path class="qvbbl6ipz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:cutter" {...props}></Icon>
