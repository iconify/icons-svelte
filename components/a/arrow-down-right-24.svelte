<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3b46jbqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b3b46jbqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:arrow-down-right-24" {...props}></Icon>
