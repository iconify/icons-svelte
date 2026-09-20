<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb4ipdb3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="kb4ipdb3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:alarm-clock" {...props}></Icon>
