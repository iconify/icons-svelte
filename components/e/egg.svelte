<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/levlm-upq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-2};
const content = `<path class="levlm-upq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:egg" {...props}></Icon>
