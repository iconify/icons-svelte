<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4-my4brf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t4-my4brf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:microfocus" {...props}></Icon>
