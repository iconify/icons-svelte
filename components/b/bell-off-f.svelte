<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt5oxot2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-1.5};
const content = `<path class="gt5oxot2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:bell-off-f" {...props}></Icon>
