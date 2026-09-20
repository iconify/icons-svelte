<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aueef1qey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="aueef1qey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:medical-doctor" {...props}></Icon>
