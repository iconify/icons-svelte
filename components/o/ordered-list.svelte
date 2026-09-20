<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sef8rzbht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-6};
const content = `<path class="sef8rzbht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:ordered-list" {...props}></Icon>
