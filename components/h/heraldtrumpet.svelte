<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9_kcp0_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="w9_kcp0_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:heraldtrumpet" {...props}></Icon>
