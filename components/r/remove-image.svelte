<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ng2byr-tb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="ng2byr-tb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:remove-image" {...props}></Icon>
