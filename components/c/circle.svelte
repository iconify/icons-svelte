<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi0mne.css';
import '../../css/s/so-from-60.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hi0mne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:circle" {...props}></Icon>
