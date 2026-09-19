<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bytiv6vnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bytiv6vnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:panel-glass-door-locked" {...props}></Icon>
