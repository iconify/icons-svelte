<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olgl6e1tn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="olgl6e1tn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:loom" {...props}></Icon>
