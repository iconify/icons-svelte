<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jztotk7yn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jztotk7yn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:phone-enabled-line" {...props}></Icon>
