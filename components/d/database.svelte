<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nixdnt-qy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nixdnt-qy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:database" {...props}></Icon>
