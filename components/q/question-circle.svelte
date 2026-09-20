<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftpp8ccpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ftpp8ccpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:question-circle" {...props}></Icon>
