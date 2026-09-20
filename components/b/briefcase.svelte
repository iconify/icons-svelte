<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_fn9_bkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="q_fn9_bkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:briefcase" {...props}></Icon>
