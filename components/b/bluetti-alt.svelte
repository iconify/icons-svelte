<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kglf9cg5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kglf9cg5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bluetti-alt" {...props}></Icon>
