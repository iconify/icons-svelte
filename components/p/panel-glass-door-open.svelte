<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phof8m8ve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="phof8m8ve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:panel-glass-door-open" {...props}></Icon>
