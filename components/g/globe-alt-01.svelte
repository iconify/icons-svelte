<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwncd7vll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cwncd7vll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:globe-alt-01" {...props}></Icon>
