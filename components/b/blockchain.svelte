<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6lc9cc4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6lc9cc4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:blockchain" {...props}></Icon>
