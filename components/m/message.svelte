<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x40v4sbwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="x40v4sbwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:message" {...props}></Icon>
