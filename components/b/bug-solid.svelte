<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcxs26b9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hcxs26b9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:bug-solid" {...props}></Icon>
