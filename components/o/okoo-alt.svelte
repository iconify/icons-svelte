<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9ptq3a0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s9ptq3a0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:okoo-alt" {...props}></Icon>
