<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1_ix6bdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o1_ix6bdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:recording-studio" {...props}></Icon>
